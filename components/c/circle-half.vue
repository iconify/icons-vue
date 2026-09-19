<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/efbw3gbbv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="efbw3gbbv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs-poly:circle-half" /></template>
