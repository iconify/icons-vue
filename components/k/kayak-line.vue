<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aunidmbaq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aunidmbaq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:kayak-line" /></template>
