<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yv6bgb0wn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="yv6bgb0wn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:loaf-of-pan-bread" /></template>
