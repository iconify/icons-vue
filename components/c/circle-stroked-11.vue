<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ldqzoubhe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":11,"height":11};
const content = `<path class="ldqzoubhe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:circle-stroked-11" /></template>
