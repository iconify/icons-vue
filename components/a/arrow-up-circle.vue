<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e7ft6soej.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e7ft6soej"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi-light:arrow-up-circle" /></template>
