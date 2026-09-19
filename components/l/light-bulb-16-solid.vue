<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tomu-wbul.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="tomu-wbul"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:light-bulb-16-solid" /></template>
