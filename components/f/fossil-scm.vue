<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y3yo1jbit.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y3yo1jbit"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:fossil-scm" /></template>
