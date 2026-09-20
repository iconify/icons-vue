<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rhch32bdw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="rhch32bdw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:dyalog" /></template>
