<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e3yaeeahm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e3yaeeahm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:flask-fill" /></template>
