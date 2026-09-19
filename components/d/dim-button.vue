<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t4ravrl3d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="t4ravrl3d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-flat:dim-button" /></template>
