<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/th1k_ebsx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="th1k_ebsx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:gradle" /></template>
