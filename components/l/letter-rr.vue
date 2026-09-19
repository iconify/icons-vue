<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jbfu52bte.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="jbfu52bte"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:letter-rr" /></template>
