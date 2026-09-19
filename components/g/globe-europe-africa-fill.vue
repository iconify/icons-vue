<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ncmsvebhl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ncmsvebhl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:globe-europe-africa-fill" /></template>
