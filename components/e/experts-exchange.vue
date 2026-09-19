<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sdvsvtb8m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="sdvsvtb8m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:experts-exchange" /></template>
