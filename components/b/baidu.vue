<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ngl4_3bgm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":432,"height":488};
const content = `<path class="ngl4_3bgm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:baidu" /></template>
