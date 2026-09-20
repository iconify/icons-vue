<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ekqu4_gnq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ekqu4_gnq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:fat-arrow-left-solid" /></template>
