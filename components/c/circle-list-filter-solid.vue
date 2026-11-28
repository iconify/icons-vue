<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/amj_hoytj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="amj_hoytj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:circle-list-filter-solid" /></template>
