<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kf4uuwbti.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":432,"height":384};
const content = `<path class="kf4uuwbti"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:aspect-ratio" /></template>
