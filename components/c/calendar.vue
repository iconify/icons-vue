<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y8q_w5_vn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="y8q_w5_vn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:calendar" /></template>
