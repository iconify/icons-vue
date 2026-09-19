<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oafi4yb8y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oafi4yb8y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:head-filled" /></template>
