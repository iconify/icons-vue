<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l4i59nbxe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<circle class="l4i59nbxe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:circle-full-stroke-12" /></template>
