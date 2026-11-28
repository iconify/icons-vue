<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jyr86z2_k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="jyr86z2_k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:image-slash-thin" /></template>
