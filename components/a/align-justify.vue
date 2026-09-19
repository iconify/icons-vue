<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rzrc6-c5z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rzrc6-c5z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codex:align-justify" /></template>
