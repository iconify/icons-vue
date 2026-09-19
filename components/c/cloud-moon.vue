<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ioxgoz4jx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ioxgoz4jx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:cloud-moon" /></template>
