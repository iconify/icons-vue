<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jaxt6_bwl.css';
import '../../css/x/x4jziszvm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="jaxt6_bwl"/><path class="x4jziszvm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:character-integer" /></template>
