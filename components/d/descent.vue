<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/esp1oilti.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="esp1oilti"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:descent" /></template>
