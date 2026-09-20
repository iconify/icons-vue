<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nlkp8bqjn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nlkp8bqjn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:file-shred-line" /></template>
