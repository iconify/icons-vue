<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r4k3to8hc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="r4k3to8hc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:binoculars" /></template>
