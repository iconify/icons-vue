<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y1f2bvbaq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y1f2bvbaq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="prime:file-word" /></template>
