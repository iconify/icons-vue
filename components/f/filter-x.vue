<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k9tt2uonp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k9tt2uonp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:filter-x" /></template>
