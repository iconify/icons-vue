<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z5_iwcr4t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="z5_iwcr4t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:disroot" /></template>
