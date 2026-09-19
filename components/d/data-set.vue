<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oph9_fobs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="oph9_fobs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:data-set" /></template>
