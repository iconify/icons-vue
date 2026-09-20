<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h07tfzb-c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="h07tfzb-c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:bluetooth-disabled" /></template>
