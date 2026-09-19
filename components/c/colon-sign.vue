<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z8g9m3umn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":512};
const content = `<path class="z8g9m3umn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:colon-sign" /></template>
