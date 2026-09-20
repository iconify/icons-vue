<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hbs3f-s9t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="hbs3f-s9t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:interface-essential-dial-pad-1" /></template>
