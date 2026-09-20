<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pc3y2574i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pc3y2574i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:letter-w-solid" /></template>
