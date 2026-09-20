<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/isy_o2iqz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="isy_o2iqz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:chevron-up-right" /></template>
