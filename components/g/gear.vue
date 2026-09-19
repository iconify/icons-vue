<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ebrv74bqa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ebrv74bqa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:gear" /></template>
