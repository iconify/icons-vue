<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/juu2knbmb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="juu2knbmb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:escalator-down-line" /></template>
