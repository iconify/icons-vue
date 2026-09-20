<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mdt0fxxjm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="mdt0fxxjm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:format-text-multiline" /></template>
