<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k665-1bdr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="k665-1bdr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:keyboard" /></template>
