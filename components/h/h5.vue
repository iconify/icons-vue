<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yws0--ucd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yws0--ucd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codex:h5" /></template>
