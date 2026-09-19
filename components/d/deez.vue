<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/msz3ifwoi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="msz3ifwoi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:deez" /></template>
