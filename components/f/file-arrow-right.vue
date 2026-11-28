<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ntus0v-mt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ntus0v-mt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:file-arrow-right" /></template>
