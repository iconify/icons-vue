<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qyyx4s3jh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="qyyx4s3jh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:battery-warn-bold" /></template>
