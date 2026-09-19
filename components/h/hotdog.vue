<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u9dxdtb8l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="u9dxdtb8l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:hotdog" /></template>
