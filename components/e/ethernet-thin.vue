<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nc05hybdw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="nc05hybdw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:ethernet-thin" /></template>
