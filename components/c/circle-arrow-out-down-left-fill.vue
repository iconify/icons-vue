<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m39rcgbnl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m39rcgbnl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:circle-arrow-out-down-left-fill" /></template>
