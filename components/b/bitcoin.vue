<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/snk5pxbny.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="snk5pxbny"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-brands:bitcoin" /></template>
