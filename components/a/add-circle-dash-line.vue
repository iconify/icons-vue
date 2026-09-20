<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gyk2onbgj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gyk2onbgj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:add-circle-dash-line" /></template>
