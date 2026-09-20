<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eqmrd89er.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eqmrd89er"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:get" /></template>
