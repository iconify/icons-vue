<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pn904sb1l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="pn904sb1l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:delay" /></template>
