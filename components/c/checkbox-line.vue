<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/axe1i_vwc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="axe1i_vwc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:checkbox-line" /></template>
