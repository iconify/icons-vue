<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9u66cceo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s9u66cceo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:bag-suitcase-off" /></template>
