<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fd1qxibnm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fd1qxibnm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:calculator-solid" /></template>
