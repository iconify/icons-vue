<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cdm514-yt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cdm514-yt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:dumbbell-outline" /></template>
