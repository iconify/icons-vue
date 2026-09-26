<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g232_jeaf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="g232_jeaf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:content-navigator-sync-error" /></template>
