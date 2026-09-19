<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/va83vo2ru.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="va83vo2ru"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fad:keyboard" /></template>
