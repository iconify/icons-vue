<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xachhj26g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xachhj26g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="weui:discover-outlined" /></template>
