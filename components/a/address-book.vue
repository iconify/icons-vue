<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tsiwd6bcp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="tsiwd6bcp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:address-book" /></template>
