<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/njoz_4bpc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="njoz_4bpc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:events" /></template>
