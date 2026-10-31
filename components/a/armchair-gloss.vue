<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aubsb5bgr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aubsb5bgr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:armchair-gloss" /></template>
