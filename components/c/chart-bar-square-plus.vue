<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l3746f4im.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="l3746f4im"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:chart-bar-square-plus" /></template>
