<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pdt01_b4z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pdt01_b4z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:battery-charging-four-solid" /></template>
