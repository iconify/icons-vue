<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g2477kbfx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g2477kbfx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:arrow-left-fill" /></template>
