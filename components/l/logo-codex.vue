<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dz32hfa-v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="dz32hfa-v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:logo-codex" /></template>
