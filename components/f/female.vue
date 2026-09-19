<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jq-pjebth.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1280,"height":1760};
const content = `<path class="jq-pjebth"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:female" /></template>
