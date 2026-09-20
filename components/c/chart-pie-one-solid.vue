<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sx9tpwuxl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sx9tpwuxl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:chart-pie-one-solid" /></template>
