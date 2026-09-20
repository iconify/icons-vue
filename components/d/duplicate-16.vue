<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d_yba3x_g.css';
import '../../css/z/zr9odabgf.css';
import '../../css/h/h5_t-db-b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="d_yba3x_g"/><path class="zr9odabgf"/><path class="h5_t-db-b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:duplicate-16" /></template>
