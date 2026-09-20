<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bmmi8805w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bmmi8805w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:audio-description-2-ai" /></template>
