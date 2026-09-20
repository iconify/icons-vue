<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uipj-oqpj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="uipj-oqpj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:bong" /></template>
