<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nr38msbnw.css';
import '../../css/h/h_c37acgj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="nr38msbnw"/><path class="h_c37acgj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:goods-filled" /></template>
