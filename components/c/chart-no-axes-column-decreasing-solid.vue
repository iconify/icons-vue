<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nxo9y8bkc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nxo9y8bkc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:chart-no-axes-column-decreasing-solid" /></template>
