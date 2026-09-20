<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/riad1mbxn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="riad1mbxn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:chart-pie" /></template>
