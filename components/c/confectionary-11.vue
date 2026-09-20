<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ae2586d8i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":11,"height":11};
const content = `<path class="ae2586d8i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:confectionary-11" /></template>
