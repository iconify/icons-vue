<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bxr7eibdy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="bxr7eibdy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:border-all-duo" /></template>
