<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/juxp6ccai.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="juxp6ccai"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:arrow-undo-up-right" /></template>
