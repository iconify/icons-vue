<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pdt1j_b8c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="pdt1j_b8c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oi:code" /></template>
