<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tc0ixizio.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tc0ixizio"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:add-circle-dash-fill" /></template>
