<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y-774wb8x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="y-774wb8x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:bison-on-zoo-uppercase" /></template>
