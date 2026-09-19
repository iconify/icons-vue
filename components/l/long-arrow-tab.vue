<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hg8nhebwc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":384};
const content = `<path class="hg8nhebwc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:long-arrow-tab" /></template>
