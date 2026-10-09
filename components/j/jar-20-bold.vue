<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pfhtqhbtz.css';
import '../../css/d/du0tax8oo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="pfhtqhbtz"/><path class="du0tax8oo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:jar-20-bold" /></template>
