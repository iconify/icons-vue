<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iv-lpchyh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="iv-lpchyh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:currency-pound-16-solid" /></template>
