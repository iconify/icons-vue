<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cyoxq9mwi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cyoxq9mwi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:bell-sleep-outline" /></template>
