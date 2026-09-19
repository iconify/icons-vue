<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ytw2g9bvj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ytw2g9bvj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dashicons:align-wide" /></template>
