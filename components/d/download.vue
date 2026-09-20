<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tb2hu2lmi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="tb2hu2lmi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zondicons:download" /></template>
