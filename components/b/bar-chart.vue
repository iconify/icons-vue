<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lsu_n2y9k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lsu_n2y9k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codex:bar-chart" /></template>
