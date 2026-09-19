<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j7-k3_nsq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j7-k3_nsq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:car-battery-filled" /></template>
