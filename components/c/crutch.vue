<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v5_kgwi9z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="v5_kgwi9z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:crutch" /></template>
