<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ruemn0m6f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ruemn0m6f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:google-analytics" /></template>
