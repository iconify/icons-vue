<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y06zqfbtb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="y06zqfbtb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:cocoapods" /></template>
