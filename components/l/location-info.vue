<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ld2931_iv.css';
import '../../css/s/s9ab3vb3q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ld2931_iv"/><path class="s9ab3vb3q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:location-info" /></template>
