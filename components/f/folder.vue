<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xo30agb-f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="xo30agb-f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:folder" /></template>
