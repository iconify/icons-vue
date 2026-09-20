<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rnl50ebfd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rnl50ebfd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:door-sliding-open" /></template>
