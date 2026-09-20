<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hv9xkx0md.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hv9xkx0md"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:abstract" /></template>
