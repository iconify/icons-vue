<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/let3ambub.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2368,"height":1664};
const content = `<path class="let3ambub"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vs:bc-card" /></template>
