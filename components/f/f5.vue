<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ryss1iurn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ryss1iurn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:f5" /></template>
