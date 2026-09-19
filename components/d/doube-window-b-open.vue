<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dfajulefx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dfajulefx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:doube-window-b-open" /></template>
