<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tdsjkub6i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tdsjkub6i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:lightbulb-flash-line" /></template>
