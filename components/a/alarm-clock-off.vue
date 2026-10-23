<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yho6uza5z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yho6uza5z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:alarm-clock-off" /></template>
