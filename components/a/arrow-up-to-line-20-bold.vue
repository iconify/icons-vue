<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wdilgkbdd.css';
import '../../css/f/fqlu4irdr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="wdilgkbdd"/><path class="fqlu4irdr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:arrow-up-to-line-20-bold" /></template>
