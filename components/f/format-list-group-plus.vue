<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/srqiojbzz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="srqiojbzz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:format-list-group-plus" /></template>
