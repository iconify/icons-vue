<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p01z6lbzt.css';
import '../../css/i/i_j_eybcb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="p01z6lbzt"/><path class="i_j_eybcb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:align-box-middle-center" /></template>
