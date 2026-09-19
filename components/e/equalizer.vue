<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jv33s8bwk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jv33s8bwk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:equalizer" /></template>
