<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h3eh006vs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h3eh006vs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:fortinet" /></template>
