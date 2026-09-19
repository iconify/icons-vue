<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vxq9lab-m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vxq9lab-m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:laugh-filled" /></template>
