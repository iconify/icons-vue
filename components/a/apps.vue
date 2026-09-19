<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h1z83msli.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":344,"height":384};
const content = `<path class="h1z83msli"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:apps" /></template>
