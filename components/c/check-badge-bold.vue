<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q482qm2fb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="q482qm2fb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:check-badge-bold" /></template>
