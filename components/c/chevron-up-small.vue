<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tc4x_wb4t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="tc4x_wb4t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:chevron-up-small" /></template>
