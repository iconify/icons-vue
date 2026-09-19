<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ef3ym8b9k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":472,"height":480};
const content = `<path class="ef3ym8b9k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:group" /></template>
