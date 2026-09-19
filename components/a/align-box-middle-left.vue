<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p01z6lbzt.css';
import '../../css/r/rt6ctoidb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="p01z6lbzt"/><path class="rt6ctoidb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:align-box-middle-left" /></template>
