<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j57k96fxe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j57k96fxe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:calendar-edit-corner-round" /></template>
