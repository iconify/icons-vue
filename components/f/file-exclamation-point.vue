<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c59ji3bwf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c59ji3bwf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:file-exclamation-point" /></template>
