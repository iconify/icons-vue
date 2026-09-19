<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ia8cb7bjb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":1023};
const content = `<path class="ia8cb7bjb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:debug" /></template>
