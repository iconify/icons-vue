<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fd2ba26lp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":1024};
const content = `<path class="fd2ba26lp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:calcmultiply" /></template>
