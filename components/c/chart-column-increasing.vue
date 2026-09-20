<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rt4jk-xcn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rt4jk-xcn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:chart-column-increasing" /></template>
