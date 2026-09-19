<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ee-cf28xs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="ee-cf28xs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:exclamationsign" /></template>
