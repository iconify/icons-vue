<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pvq1r7byr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pvq1r7byr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:arrow-long-up-right-solid" /></template>
