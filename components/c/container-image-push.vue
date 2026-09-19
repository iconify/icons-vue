<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dymyxwbeh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="dymyxwbeh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:container-image-push" /></template>
