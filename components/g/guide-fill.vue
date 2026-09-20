<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e0zkh6bgw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e0zkh6bgw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:guide-fill" /></template>
