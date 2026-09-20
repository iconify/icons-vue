<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ccfpk9bpa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ccfpk9bpa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:alarm-2-line" /></template>
