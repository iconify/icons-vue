<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hh07jkbkl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hh07jkbkl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:bulb-sultan-off" /></template>
