<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x1ooo089j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x1ooo089j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:arrow-down-right-waves-solid" /></template>
