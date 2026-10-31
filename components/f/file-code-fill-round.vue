<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rbilo7g8f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rbilo7g8f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:file-code-fill-round" /></template>
