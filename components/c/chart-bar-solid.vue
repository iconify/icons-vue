<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zpyix5bgu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zpyix5bgu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:chart-bar-solid" /></template>
