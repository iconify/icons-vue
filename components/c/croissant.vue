<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xr0i7lbyq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="xr0i7lbyq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:croissant" /></template>
