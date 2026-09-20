<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cm1oe6iah.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":384};
const content = `<path class="cm1oe6iah"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:framer-light" /></template>
