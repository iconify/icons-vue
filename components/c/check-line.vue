<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jhy5-hkxr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jhy5-hkxr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:check-line" /></template>
