<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/larxflb5e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="larxflb5e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="meteor-icons:github-copilot" /></template>
