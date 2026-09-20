<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fkzwb8bsi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fkzwb8bsi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:book-open-line" /></template>
