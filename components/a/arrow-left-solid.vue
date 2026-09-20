<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qwtw7fjrr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qwtw7fjrr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:arrow-left-solid" /></template>
