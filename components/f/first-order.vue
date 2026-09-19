<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ngi88-baq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="ngi88-baq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-brands:first-order" /></template>
