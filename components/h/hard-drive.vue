<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/um8k7-jvx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="um8k7-jvx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:hard-drive" /></template>
