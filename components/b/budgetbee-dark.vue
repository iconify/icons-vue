<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uthnkib2i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="uthnkib2i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:budgetbee-dark" /></template>
