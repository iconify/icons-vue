<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j8pwlvbfx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j8pwlvbfx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:add-queue" /></template>
