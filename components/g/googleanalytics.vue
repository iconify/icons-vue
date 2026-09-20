<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zc-nk8b0n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zc-nk8b0n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:googleanalytics" /></template>
