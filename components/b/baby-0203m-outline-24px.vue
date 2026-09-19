<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ulox7yzfw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ulox7yzfw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:baby-0203m-outline-24px" /></template>
