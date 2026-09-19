<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/axud5abfm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="axud5abfm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:circle-question" /></template>
