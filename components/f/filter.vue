<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o6s466b-b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="o6s466b-b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:filter" /></template>
