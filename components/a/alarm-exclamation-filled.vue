<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pg4551bmt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pg4551bmt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:alarm-exclamation-filled" /></template>
