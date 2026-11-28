<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l6ag-dbku.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l6ag-dbku"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:cloud-download-check" /></template>
