<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o-1z7t7dt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o-1z7t7dt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:bread-slice" /></template>
