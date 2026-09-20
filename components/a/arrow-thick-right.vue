<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z1blmymmd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="z1blmymmd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oi:arrow-thick-right" /></template>
