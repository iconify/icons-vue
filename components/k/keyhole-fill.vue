<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wkoqdlsxc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wkoqdlsxc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:keyhole-fill" /></template>
