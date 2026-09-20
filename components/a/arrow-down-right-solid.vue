<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gilks3ujm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gilks3ujm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:arrow-down-right-solid" /></template>
