<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ll7qgv_ez.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="ll7qgv_ez"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:file-export" /></template>
