<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rnf84jbzt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rnf84jbzt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:dock-top" /></template>
