<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hu_t3tbfu.css';
import '../../css/s/syzt_cbmk.css';
import '../../css/n/n0oj8po7r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="hu_t3tbfu"/><path class="syzt_cbmk"/><path class="n0oj8po7r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:imbalance-20" /></template>
