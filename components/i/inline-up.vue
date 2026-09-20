<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i90gq365a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="i90gq365a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="quill:inline-up" /></template>
