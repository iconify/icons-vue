<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rfchu_-gh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="rfchu_-gh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:flow-connection" /></template>
