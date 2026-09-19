<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w_dq43bgv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="w_dq43bgv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:house-fire-outline" /></template>
