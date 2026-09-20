<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x2xw--bfz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x2xw--bfz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:cake-2-fill" /></template>
