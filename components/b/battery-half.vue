<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dalli1b-e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dalli1b-e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:battery-half" /></template>
