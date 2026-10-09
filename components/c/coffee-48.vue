<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pfg1jelsz.css';
import '../../css/f/fec_ntl8c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="pfg1jelsz"/><path class="fec_ntl8c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:coffee-48" /></template>
