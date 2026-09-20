<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cykb50bxp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="cykb50bxp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:circle-filled" /></template>
