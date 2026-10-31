<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f05dbwbtr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f05dbwbtr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:circle-chevron-double-up-fill-round" /></template>
