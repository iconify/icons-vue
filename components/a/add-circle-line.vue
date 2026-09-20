<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yh0i2rbwo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yh0i2rbwo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:add-circle-line" /></template>
