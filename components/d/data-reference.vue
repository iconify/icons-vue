<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gut_bzbno.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="gut_bzbno"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:data-reference" /></template>
