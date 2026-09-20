<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qgj-x05-m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qgj-x05-m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:chart-column-stacked-sharp" /></template>
