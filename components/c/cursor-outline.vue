<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c_gb48rxr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="c_gb48rxr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:cursor-outline" /></template>
