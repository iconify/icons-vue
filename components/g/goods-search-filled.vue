<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iv5pi-bzy.css';
import '../../css/c/crj_bc0sa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="iv5pi-bzy"/><path clip-rule="evenodd" class="crj_bc0sa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:goods-search-filled" /></template>
