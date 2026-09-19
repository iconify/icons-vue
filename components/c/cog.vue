<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wxdp1rbfv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="wxdp1rbfv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:cog" /></template>
