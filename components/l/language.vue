<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mgqdux_eq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1536,"height":1792};
const content = `<path class="mgqdux_eq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:language" /></template>
