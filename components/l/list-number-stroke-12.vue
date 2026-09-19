<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x9frmbbrf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="x9frmbbrf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:list-number-stroke-12" /></template>
