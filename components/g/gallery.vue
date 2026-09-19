<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vs4r5cb6d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vs4r5cb6d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="guidance:gallery" /></template>
