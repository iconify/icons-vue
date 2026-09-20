<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uf9im3bmj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uf9im3bmj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:cloud-hail" /></template>
