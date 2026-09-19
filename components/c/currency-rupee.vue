<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sddv5gf_x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="sddv5gf_x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:currency-rupee" /></template>
