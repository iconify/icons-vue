<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ypw2v6byn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ypw2v6byn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:calendar-slash-solid" /></template>
