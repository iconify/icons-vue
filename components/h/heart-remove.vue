<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n8oswccha.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":21,"height":21};
const content = `<path class="n8oswccha"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="system-uicons:heart-remove" /></template>
