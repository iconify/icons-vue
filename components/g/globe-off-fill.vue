<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yoc2j8l5k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yoc2j8l5k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:globe-off-fill" /></template>
