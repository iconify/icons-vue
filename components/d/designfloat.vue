<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/isyw8ybmv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":464,"height":488};
const content = `<path class="isyw8ybmv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:designfloat" /></template>
