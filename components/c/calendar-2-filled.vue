<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w9y0cgola.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w9y0cgola"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:calendar-2-filled" /></template>
