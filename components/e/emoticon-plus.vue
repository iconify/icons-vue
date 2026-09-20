<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hnuy-zbdb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hnuy-zbdb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:emoticon-plus" /></template>
