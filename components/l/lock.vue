<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3tshpbbi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":344,"height":456};
const content = `<path class="v3tshpbbi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:lock" /></template>
