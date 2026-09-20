<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w1t12mxhu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w1t12mxhu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:generic-device-restart" /></template>
