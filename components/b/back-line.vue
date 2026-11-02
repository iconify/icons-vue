<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jlxpr7-2p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jlxpr7-2p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:back-line" /></template>
