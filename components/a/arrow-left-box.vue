<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j031vob3m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j031vob3m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:arrow-left-box" /></template>
