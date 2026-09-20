<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uq1hn912b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="uq1hn912b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:cellular-network-5g" /></template>
