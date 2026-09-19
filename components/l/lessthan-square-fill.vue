<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m6iis_xvt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="m6iis_xvt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:lessthan-square-fill" /></template>
