<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ehhu9f5ds.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ehhu9f5ds"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-right-top-arrow-circle" /></template>
