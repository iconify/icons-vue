<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mu47fn-nw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mu47fn-nw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:drag-drop-line" /></template>
