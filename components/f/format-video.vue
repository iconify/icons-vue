<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o_t083bvv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="o_t083bvv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dashicons:format-video" /></template>
