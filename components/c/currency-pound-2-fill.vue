<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q28ow0buv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q28ow0buv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:currency-pound-2-fill" /></template>
