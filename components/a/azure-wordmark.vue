<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/de1j8m3zv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="de1j8m3zv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:azure-wordmark" /></template>
