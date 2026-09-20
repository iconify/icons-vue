<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eb7wkv_1h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="eb7wkv_1h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="osmic:castle-stately-14" /></template>
