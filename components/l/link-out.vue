<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/knszhabor.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="knszhabor"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="quill:link-out" /></template>
