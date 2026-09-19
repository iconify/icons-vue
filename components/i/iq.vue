<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/itu_xpbfo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="itu_xpbfo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:iq" /></template>
