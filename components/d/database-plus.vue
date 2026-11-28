<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wyfb50n_r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wyfb50n_r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:database-plus" /></template>
