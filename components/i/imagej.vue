<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wtq0b4b6i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wtq0b4b6i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:imagej" /></template>
