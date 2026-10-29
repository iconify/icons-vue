<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hdvspgbei.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hdvspgbei"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:bluetooth-connected" /></template>
