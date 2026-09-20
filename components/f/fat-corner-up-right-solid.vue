<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p788krbnx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p788krbnx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:fat-corner-up-right-solid" /></template>
