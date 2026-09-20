<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x37jg-vpa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="x37jg-vpa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="academicons:elsevier-square" /></template>
