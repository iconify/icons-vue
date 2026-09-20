<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hgs60lb1t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="hgs60lb1t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:linkedin-in" /></template>
