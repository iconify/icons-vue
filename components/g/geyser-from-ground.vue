<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fv5vt-b3k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="fv5vt-b3k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:geyser-from-ground" /></template>
