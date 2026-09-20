<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n8j07dwip.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="n8j07dwip"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:app-store-ios" /></template>
