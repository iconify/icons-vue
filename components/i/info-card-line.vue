<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/omzwo4lej.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="omzwo4lej"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:info-card-line" /></template>
