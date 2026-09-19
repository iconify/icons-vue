<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sqkkoobdf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sqkkoobdf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fe:align-center" /></template>
