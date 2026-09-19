<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uyb6fervv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":512};
const content = `<path class="uyb6fervv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:file-excel" /></template>
