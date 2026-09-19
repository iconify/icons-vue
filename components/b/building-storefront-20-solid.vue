<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rvycimbwd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="rvycimbwd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:building-storefront-20-solid" /></template>
