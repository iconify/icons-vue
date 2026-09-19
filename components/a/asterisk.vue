<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mkt2k58qj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="mkt2k58qj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icons8:asterisk" /></template>
