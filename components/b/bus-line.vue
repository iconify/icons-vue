<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q3g2j8bae.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q3g2j8bae"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:bus-line" /></template>
