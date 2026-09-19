<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m4hofbbri.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="m4hofbbri"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:ibm-vsi-on-vpc-for-regulated-industries" /></template>
