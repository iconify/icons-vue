<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iuun5oelc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iuun5oelc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:door-line" /></template>
