<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s-3o2v47x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s-3o2v47x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:clipboard-copy-line" /></template>
