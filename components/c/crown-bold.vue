<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kmfyb8myx.css';
import '../../css/d/dxwhy-b8i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kmfyb8myx"/><path class="dxwhy-b8i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:crown-bold" /></template>
