<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/td-efsbyx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="td-efsbyx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:ceiling-runner-three" /></template>
