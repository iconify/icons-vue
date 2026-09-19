<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xr5ki4baj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="xr5ki4baj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:light-bulb-20-solid" /></template>
