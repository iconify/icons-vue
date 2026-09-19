<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ujbvu5b5g.css';
import '../../css/o/omc5y5yrn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ujbvu5b5g"/><path class="omc5y5yrn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:ethos" /></template>
