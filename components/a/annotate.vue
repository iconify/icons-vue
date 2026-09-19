<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zdn2mabuv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="zdn2mabuv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="foundation:annotate" /></template>
