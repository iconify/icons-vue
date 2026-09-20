<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rqpyn9bia.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rqpyn9bia"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uis:battery-empty" /></template>
