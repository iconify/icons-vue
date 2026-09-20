<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lwvaa_2fz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lwvaa_2fz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:circle-arrow-up" /></template>
