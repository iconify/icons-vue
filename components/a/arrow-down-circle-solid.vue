<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wj8hssxit.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wj8hssxit"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:arrow-down-circle-solid" /></template>
