<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sf5x249yi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="sf5x249yi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:fontcaligraphy" /></template>
