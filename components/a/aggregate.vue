<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft4l_3bzc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ft4l_3bzc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oui:aggregate" /></template>
