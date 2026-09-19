<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o1amxv-5z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="o1amxv-5z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dashicons:cloud" /></template>
