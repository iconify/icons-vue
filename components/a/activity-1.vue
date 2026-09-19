<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v6aq-f6ay.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="v6aq-f6ay"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs-poly:activity-1" /></template>
