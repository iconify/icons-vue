<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uz9exbb3k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="uz9exbb3k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:file-signature" /></template>
