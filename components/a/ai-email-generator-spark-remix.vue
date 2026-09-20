<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hvyksh09g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="hvyksh09g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:ai-email-generator-spark-remix" /></template>
