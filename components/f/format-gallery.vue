<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x27_uqb0e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="x27_uqb0e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dashicons:format-gallery" /></template>
