<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rotb33b9k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":35,"height":24};
const content = `<path class="rotb33b9k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:jsfiddle" /></template>
