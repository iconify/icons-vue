<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h2qh98usm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="h2qh98usm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-flat:cyclone" /></template>
