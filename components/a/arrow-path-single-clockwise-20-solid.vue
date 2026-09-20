<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x5b0hsbts.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="x5b0hsbts"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:arrow-path-single-clockwise-20-solid" /></template>
