<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cj3_jnb8x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="cj3_jnb8x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:eaved-open-gabled-building-with-window" /></template>
