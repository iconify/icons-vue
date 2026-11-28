<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zwg2ogbkm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="primary zwg2ogbkm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:grid-dots-duotone" /></template>
