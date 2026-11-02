<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aiiu3qbud.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aiiu3qbud"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:flag-2-fill" /></template>
