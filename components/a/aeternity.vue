<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vg6mo1bgc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vg6mo1bgc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:aeternity" /></template>
