<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hue27w-ln.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hue27w-ln"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:file" /></template>
