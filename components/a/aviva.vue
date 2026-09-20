<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xl59vwg3r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":161,"height":56};
const content = `<path clip-rule="evenodd" class="xl59vwg3r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:aviva" /></template>
