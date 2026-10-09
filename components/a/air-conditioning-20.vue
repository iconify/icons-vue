<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mxqh80bxh.css';
import '../../css/n/nxwt419zs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="mxqh80bxh"/><path class="nxwt419zs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:air-conditioning-20" /></template>
