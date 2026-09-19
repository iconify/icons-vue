<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lqhgtqdtq.css';
import '../../css/c/c924plbqp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lqhgtqdtq"/><path class="c924plbqp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:arrow-out-up-left-square-filled" /></template>
