<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/weyd5pbzu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="weyd5pbzu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:clef-alto" /></template>
