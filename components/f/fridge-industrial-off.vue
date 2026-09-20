<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tcb628byz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tcb628byz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:fridge-industrial-off" /></template>
