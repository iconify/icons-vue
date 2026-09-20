<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s-vi7nafh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s-vi7nafh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:file-multiple-outline" /></template>
