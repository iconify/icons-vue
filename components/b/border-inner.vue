<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oke-pbcno.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":384};
const content = `<path class="oke-pbcno"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:border-inner" /></template>
