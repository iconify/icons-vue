<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fzkptq_9i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="fzkptq_9i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:file-invoice-solid" /></template>
