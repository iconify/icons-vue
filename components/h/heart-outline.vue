<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tlysr-wwq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="tlysr-wwq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:heart-outline" /></template>
