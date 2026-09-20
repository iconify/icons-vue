<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/azkx3ab1h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="azkx3ab1h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:bible-solid" /></template>
