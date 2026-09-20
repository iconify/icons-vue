<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wzfqp_bxg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="wzfqp_bxg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:badge-promotion-outline" /></template>
