<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dk5l3_60h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dk5l3_60h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="weui:folder-outlined" /></template>
