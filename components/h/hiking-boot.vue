<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ukwwe_bgv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ukwwe_bgv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:hiking-boot" /></template>
