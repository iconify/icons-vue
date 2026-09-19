<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eln8b-54w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":13,"height":24};
const content = `<path class="eln8b-54w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:bookmark-alt" /></template>
