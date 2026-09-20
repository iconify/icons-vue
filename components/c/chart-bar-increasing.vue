<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pwrs7pbyk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pwrs7pbyk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:chart-bar-increasing" /></template>
