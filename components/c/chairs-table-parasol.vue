<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t1586_51s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t1586_51s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-lab:chairs-table-parasol" /></template>
