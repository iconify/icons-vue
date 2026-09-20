<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e03d1ubcp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e03d1ubcp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uit:horizontal-align-left" /></template>
