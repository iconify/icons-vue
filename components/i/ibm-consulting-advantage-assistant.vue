<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nuoycycep.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="nuoycycep"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:ibm-consulting-advantage-assistant" /></template>
