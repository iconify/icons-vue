<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pigc8jqvk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="pigc8jqvk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:image-plus-fill" /></template>
