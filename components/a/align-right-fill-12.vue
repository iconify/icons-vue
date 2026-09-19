<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bnhnnwbfd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="bnhnnwbfd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:align-right-fill-12" /></template>
