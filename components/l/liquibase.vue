<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nn_tx-8bl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nn_tx-8bl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:liquibase" /></template>
