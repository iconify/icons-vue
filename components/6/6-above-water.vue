<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mw6abvbbq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="mw6abvbbq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:6-above-water" /></template>
