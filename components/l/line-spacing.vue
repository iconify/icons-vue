<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wxv-nlb9z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wxv-nlb9z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uit:line-spacing" /></template>
