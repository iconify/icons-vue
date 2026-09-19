<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g75be7uzv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="g75be7uzv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:ibm-engineering-systems-design-rhapsody-sn1" /></template>
