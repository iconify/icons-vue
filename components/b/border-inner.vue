<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xoc4ocbwg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xoc4ocbwg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uis:border-inner" /></template>
