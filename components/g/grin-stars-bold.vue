<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xrl0tvb8t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="xrl0tvb8t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:grin-stars-bold" /></template>
