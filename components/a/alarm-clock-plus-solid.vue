<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vh0succoc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vh0succoc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:alarm-clock-plus-solid" /></template>
