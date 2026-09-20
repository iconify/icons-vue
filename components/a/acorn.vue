<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rdglqd46z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="rdglqd46z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:acorn" /></template>
