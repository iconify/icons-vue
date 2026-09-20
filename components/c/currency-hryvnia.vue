<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ngd1m3bou.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ngd1m3bou"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:currency-hryvnia" /></template>
