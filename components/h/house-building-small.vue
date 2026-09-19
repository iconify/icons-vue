<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fh9zjpb0f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="fh9zjpb0f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:house-building-small" /></template>
