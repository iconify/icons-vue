<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dve4gcewv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="dve4gcewv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:cloud-hail-20-bold" /></template>
