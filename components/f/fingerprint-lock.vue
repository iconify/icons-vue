<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dpnbl9yww.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dpnbl9yww"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:fingerprint-lock" /></template>
