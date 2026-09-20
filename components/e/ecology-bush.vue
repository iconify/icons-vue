<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s6pzp95xe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="s6pzp95xe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:ecology-bush" /></template>
