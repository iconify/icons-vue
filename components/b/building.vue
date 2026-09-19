<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dn_dgl-by.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="dn_dgl-by"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:building" /></template>
