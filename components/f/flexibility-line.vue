<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vzjxaibce.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vzjxaibce"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:flexibility-line" /></template>
