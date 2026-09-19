<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v27ipbc-t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":500,"height":1000};
const content = `<path class="v27ipbc-t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="brandico:diigo" /></template>
