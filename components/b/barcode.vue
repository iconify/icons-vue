<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l5ao1-bsw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":768,"height":644};
const content = `<path class="l5ao1-bsw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:barcode" /></template>
