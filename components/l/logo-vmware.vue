<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hvsm9lbfr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="hvsm9lbfr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:logo-vmware" /></template>
