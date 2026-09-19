<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h56kjmbec.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":17};
const content = `<path class="h56kjmbec"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:arrow-two-up" /></template>
