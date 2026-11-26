<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kjqb2rzwv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":500,"height":500};
const content = `<path class="kjqb2rzwv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:intelbyte" /></template>
