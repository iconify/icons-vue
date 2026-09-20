<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p333-tb1i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p333-tb1i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:atm" /></template>
