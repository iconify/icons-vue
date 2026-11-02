<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cu1yncb7g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cu1yncb7g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:close-circle-line" /></template>
