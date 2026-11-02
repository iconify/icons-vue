<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oms3i8bby.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oms3i8bby"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:folder-star-line" /></template>
