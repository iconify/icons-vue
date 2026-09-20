<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/ggep1bc6h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ggep1bc6h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:book-medical-solid" /></template>
