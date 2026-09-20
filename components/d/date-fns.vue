<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/km3_h9but.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="km3_h9but"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:date-fns" /></template>
