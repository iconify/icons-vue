<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dzhx1bcdv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="dzhx1bcdv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:boxes-stacked" /></template>
