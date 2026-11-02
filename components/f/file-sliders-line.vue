<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uk2by8bha.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uk2by8bha"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:file-sliders-line" /></template>
