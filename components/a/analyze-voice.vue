<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o9rl3mb6m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="o9rl3mb6m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:analyze-voice" /></template>
