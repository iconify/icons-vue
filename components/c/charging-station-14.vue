<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g-e2otb3v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="g-e2otb3v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="osmic:charging-station-14" /></template>
