<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c0cpixglr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":11,"height":11};
const content = `<path class="c0cpixglr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:hospital-jp-11" /></template>
