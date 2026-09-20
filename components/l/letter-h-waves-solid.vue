<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oum4ihblh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oum4ihblh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:letter-h-waves-solid" /></template>
