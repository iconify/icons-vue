<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/go02y2lxc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="go02y2lxc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:lipstick-line" /></template>
