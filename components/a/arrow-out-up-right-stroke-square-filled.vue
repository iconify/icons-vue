<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xrw7eflsk.css';
import '../../css/i/isu2qlb9h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xrw7eflsk"/><path class="isu2qlb9h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:arrow-out-up-right-stroke-square-filled" /></template>
