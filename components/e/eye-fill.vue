<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/osl_ewbwa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="osl_ewbwa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:eye-fill" /></template>
