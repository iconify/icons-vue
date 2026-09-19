<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pok4x5b_o.css';
import '../../css/x/xnk1gt9lb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="pok4x5b_o"/><path class="xnk1gt9lb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:file-excel" /></template>
