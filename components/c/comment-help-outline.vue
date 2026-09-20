<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e51t83bny.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e51t83bny"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:comment-help-outline" /></template>
