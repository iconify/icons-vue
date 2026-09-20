<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x1-9e5ove.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="x1-9e5ove"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:crown" /></template>
