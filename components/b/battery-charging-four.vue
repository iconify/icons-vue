<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/ti1ys_bcu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ti1ys_bcu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:battery-charging-four" /></template>
