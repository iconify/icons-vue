<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/euo93-5ut.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="euo93-5ut"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:beer" /></template>
