<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sx8ip0b3l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="sx8ip0b3l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:asterisk-stroke-16" /></template>
