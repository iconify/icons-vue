<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tlbiui_0e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tlbiui_0e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:bahai" /></template>
