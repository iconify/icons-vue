<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nd74-c-sb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nd74-c-sb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:fullscreen-2-fill" /></template>
