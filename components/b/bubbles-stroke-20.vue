<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dcbbl7i3r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="dcbbl7i3r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:bubbles-stroke-20" /></template>
