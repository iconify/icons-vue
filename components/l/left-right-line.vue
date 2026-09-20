<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gi8prk_nz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gi8prk_nz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:left-right-line" /></template>
