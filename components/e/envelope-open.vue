<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c5nlv5dar.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="c5nlv5dar"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-regular:envelope-open" /></template>
