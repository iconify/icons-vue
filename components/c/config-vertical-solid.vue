<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/van_eiakz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="van_eiakz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:config-vertical-solid" /></template>
