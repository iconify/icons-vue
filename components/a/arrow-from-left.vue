<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kei-b7but.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kei-b7but"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:arrow-from-left" /></template>
