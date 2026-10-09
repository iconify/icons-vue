<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iplcxaclv.css';
import '../../css/o/oqts9w9jb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="iplcxaclv"/><path class="oqts9w9jb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:coupling-20-bold" /></template>
