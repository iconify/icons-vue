<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p01z6lbzt.css';
import '../../css/x/xp7skg3_j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="p01z6lbzt"/><path class="xp7skg3_j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:align-box-top-center" /></template>
