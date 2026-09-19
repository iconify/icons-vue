<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nex2kb9vb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":384};
const content = `<path class="nex2kb9vb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:border-all" /></template>
