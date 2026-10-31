<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mt_2hzb_i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mt_2hzb_i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:bell-round" /></template>
