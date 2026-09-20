<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xyh3fv8ud.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xyh3fv8ud"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:hand-peace" /></template>
