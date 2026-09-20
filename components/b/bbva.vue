<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/krxl8tomz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":3543.2,"height":1059.5};
const content = `<path class="krxl8tomz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:bbva" /></template>
