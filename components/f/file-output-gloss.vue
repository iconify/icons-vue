<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i964pabbz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i964pabbz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:file-output-gloss" /></template>
