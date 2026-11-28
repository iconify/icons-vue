<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zhshecbhf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zhshecbhf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:layout-dashboard-solid" /></template>
