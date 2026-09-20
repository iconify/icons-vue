<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mxu2bz8el.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mxu2bz8el"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:eject" /></template>
