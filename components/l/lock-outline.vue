<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ibstzpbrw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":344,"height":456};
const content = `<path class="ibstzpbrw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:lock-outline" /></template>
