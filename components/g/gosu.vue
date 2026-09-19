<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d9dgodt9k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="d9dgodt9k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:gosu" /></template>
