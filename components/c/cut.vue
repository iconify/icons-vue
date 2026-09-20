<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rwd0breix.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="rwd0breix"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:cut" /></template>
