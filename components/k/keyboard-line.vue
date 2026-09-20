<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/habq1_bvu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="habq1_bvu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:keyboard-line" /></template>
