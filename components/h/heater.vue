<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/esq_-z43o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="esq_-z43o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:heater" /></template>
