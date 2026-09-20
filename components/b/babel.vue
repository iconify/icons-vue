<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i8yywaboc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1349,"height":519};
const content = `<path class="i8yywaboc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:babel" /></template>
