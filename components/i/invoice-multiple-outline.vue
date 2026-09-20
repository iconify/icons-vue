<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sjmeoibsy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sjmeoibsy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:invoice-multiple-outline" /></template>
