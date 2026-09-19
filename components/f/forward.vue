<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k7698yeng.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k7698yeng"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:forward" /></template>
