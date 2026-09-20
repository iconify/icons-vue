<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gh20bg4_s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gh20bg4_s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:invidious" /></template>
