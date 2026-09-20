<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/furzhfbfg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="furzhfbfg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:image-check" /></template>
