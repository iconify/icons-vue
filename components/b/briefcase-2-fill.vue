<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ia_s7c2er.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ia_s7c2er"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:briefcase-2-fill" /></template>
