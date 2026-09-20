<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wl72n8d-i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wl72n8d-i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uis:border-clear" /></template>
