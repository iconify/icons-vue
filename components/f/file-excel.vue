<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mvjy-drzn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mvjy-drzn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fe:file-excel" /></template>
