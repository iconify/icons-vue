<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ym1fg2b7s.css';
import '../../css/q/qmopwkg8b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ym1fg2b7s"/><path class="qmopwkg8b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:cookie-filled" /></template>
