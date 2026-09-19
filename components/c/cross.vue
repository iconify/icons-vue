<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/le4ed9yxx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="le4ed9yxx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codex:cross" /></template>
