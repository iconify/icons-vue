<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yrwqzibld.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":26.458,"height":3.704};
const content = `<path class="yrwqzibld"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:cathay-pacific" /></template>
