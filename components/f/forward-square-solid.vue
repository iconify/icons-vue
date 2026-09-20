<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kzkw3y5rh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kzkw3y5rh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:forward-square-solid" /></template>
