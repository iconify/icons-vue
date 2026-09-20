<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y0s5tbx4g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y0s5tbx4g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:alarm-minus-solid" /></template>
