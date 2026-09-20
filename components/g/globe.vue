<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dmv37bb5r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="dmv37bb5r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:globe" /></template>
