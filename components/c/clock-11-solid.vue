<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/da4_wc1jt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="da4_wc1jt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:clock-11-solid" /></template>
