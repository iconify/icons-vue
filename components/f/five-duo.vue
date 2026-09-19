<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mp7lv3bmi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="mp7lv3bmi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:five-duo" /></template>
