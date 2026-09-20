<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sukzc8bpa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="sukzc8bpa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:cloudscale" /></template>
