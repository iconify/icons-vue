<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ctnlfw3mn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ctnlfw3mn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:head-24px" /></template>
