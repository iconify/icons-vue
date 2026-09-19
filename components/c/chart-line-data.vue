<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fgyq62bby.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fgyq62bby"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:chart-line-data" /></template>
