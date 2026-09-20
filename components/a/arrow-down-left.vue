<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ak6ukobkl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ak6ukobkl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:arrow-down-left" /></template>
