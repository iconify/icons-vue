<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s80000qbg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="s80000qbg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:geyser-from-ground" /></template>
