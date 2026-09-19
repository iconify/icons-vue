<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wf8eb6b3c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="wf8eb6b3c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:ark" /></template>
