<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lx1m91mzz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="lx1m91mzz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oi:link-intact" /></template>
