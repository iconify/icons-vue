<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/exdgbrjak.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="exdgbrjak"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:grid-2-line" /></template>
