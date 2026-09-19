<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yt2gwzbgo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yt2gwzbgo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-purchase-tag" /></template>
