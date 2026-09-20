<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/etwsosu7w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="etwsosu7w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:hooli" /></template>
