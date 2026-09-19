<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yepbyis8w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yepbyis8w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:bulb-group-classic-3" /></template>
