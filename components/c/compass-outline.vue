<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tb14vtbgw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tb14vtbgw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:compass-outline" /></template>
