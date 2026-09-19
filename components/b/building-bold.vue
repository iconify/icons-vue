<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/myt_lgb1o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="myt_lgb1o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:building-bold" /></template>
