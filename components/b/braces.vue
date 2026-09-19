<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z8g1rbcqn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="z8g1rbcqn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:braces" /></template>
