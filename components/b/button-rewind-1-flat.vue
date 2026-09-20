<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q5yxx3pqf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="q5yxx3pqf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-color:button-rewind-1-flat" /></template>
