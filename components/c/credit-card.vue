<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/etwi6sbrt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="etwi6sbrt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:credit-card" /></template>
