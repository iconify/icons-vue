<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xc05s8evs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xc05s8evs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:formula-fill" /></template>
