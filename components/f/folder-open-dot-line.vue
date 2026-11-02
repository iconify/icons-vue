<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lmz4k78ew.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lmz4k78ew"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:folder-open-dot-line" /></template>
