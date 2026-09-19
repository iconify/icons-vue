<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zd12_wbjy.css';
import '../../css/i/iyp56ebds.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="zd12_wbjy"/><path class="iyp56ebds"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:link" /></template>
