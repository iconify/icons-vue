<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pshecz_7b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":320,"height":384};
const content = `<path class="pshecz_7b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:flag" /></template>
