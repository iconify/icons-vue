<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iwqc1t6co.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="iwqc1t6co"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:address-book" /></template>
