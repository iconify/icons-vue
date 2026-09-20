<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vmrbxm3qn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vmrbxm3qn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:border-bottom-variant" /></template>
