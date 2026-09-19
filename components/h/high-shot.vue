<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lvxjq0dhy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="lvxjq0dhy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:high-shot" /></template>
