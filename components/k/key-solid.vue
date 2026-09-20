<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ej0_s9byi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ej0_s9byi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:key-solid" /></template>
