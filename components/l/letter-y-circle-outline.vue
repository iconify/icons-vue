<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xtuiqcb_s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xtuiqcb_s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:letter-y-circle-outline" /></template>
