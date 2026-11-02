<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/okfw9lw1v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="okfw9lw1v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:grid-2x2-check-fill" /></template>
