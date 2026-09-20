<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/th_20f-bj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="th_20f-bj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:headset-off" /></template>
