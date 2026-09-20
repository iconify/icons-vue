<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i1x60zbjh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":55,"height":20};
const content = `<path clip-rule="evenodd" class="i1x60zbjh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:aero-light" /></template>
