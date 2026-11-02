<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mucgjlcvd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mucgjlcvd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:bell-electric-fill" /></template>
