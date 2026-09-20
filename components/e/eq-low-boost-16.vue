<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tm-51lkin.css';
import '../../css/x/x1wvsgy0b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="tm-51lkin"/><path class="x1wvsgy0b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:eq-low-boost-16" /></template>
