<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k8yegab2c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="k8yegab2c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:d-bold" /></template>
