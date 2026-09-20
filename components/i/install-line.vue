<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fmdsglb3y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fmdsglb3y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:install-line" /></template>
