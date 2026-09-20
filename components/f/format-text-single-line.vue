<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tqpy7rbyd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="tqpy7rbyd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:format-text-single-line" /></template>
