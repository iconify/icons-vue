<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t8g3lve1e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t8g3lve1e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:hospital" /></template>
