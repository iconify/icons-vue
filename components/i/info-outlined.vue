<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fwfpq_bia.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fwfpq_bia"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="weui:info-outlined" /></template>
