<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rxxnz6b3s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rxxnz6b3s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:circles" /></template>
