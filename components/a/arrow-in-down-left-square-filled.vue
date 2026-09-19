<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gu8duj-kd.css';
import '../../css/v/vxwbsu80r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gu8duj-kd"/><path class="vxwbsu80r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:arrow-in-down-left-square-filled" /></template>
