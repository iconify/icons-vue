<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wo7ddhbhi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wo7ddhbhi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eva:layers-outline" /></template>
