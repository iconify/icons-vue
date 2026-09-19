<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z06xlpj0d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":384};
const content = `<path class="z06xlpj0d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:long-arrow-up" /></template>
