<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g728b8bwm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g728b8bwm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:file-locked-line" /></template>
