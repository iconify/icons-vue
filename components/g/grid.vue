<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ap45321cx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ap45321cx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:grid" /></template>
