<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mgqeagbus.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mgqeagbus"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:focus-3-fill" /></template>
