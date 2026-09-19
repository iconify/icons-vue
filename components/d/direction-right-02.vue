<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zndv10soq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="zndv10soq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:direction-right-02" /></template>
