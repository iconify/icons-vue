<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jmsyxl2qx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jmsyxl2qx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:globe2" /></template>
