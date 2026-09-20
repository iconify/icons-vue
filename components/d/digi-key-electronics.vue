<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g7vi-tn5r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g7vi-tn5r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:digi-key-electronics" /></template>
