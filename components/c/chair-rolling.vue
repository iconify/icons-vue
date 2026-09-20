<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xpl9ltrpi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xpl9ltrpi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:chair-rolling" /></template>
