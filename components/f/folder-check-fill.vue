<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cbnhusb6w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cbnhusb6w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:folder-check-fill" /></template>
