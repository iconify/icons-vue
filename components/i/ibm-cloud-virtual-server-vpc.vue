<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o-cigyqaj.css';
import '../../css/d/dmmzmkb4s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<circle class="o-cigyqaj"/><path class="dmmzmkb4s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:ibm-cloud-virtual-server-vpc" /></template>
