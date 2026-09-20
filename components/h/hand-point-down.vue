<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w0e06xb_t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="w0e06xb_t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:hand-point-down" /></template>
