<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h2mejiiak.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="h2mejiiak"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:cafe" /></template>
