<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f9mz0in7p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f9mz0in7p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:file-reduce-line" /></template>
