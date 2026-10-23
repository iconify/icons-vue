<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bsp_bnfrk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bsp_bnfrk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:database-check" /></template>
