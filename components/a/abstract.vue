<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oud7_ne2u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="oud7_ne2u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:abstract" /></template>
