<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dimg2-ovr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="dimg2-ovr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dashicons:arrow-right-alt" /></template>
