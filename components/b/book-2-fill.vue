<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q13w98l5r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q13w98l5r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:book-2-fill" /></template>
