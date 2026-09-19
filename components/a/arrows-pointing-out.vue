<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fguy6clur.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="fguy6clur"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-solid:arrows-pointing-out" /></template>
