<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jmd8usb4q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jmd8usb4q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:battery-2-filled" /></template>
