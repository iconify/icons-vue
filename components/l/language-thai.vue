<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uzh3pe_2x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="uzh3pe_2x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:language-thai" /></template>
