<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lxbe-jsqf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="lxbe-jsqf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:i" /></template>
