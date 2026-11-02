<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pa3abwy6r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pa3abwy6r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:mail-question-mark-fill" /></template>
