<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zp1219b-m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="zp1219b-m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:deer-head" /></template>
