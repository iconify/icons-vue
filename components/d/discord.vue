<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ll9pedc-e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ll9pedc-e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:discord" /></template>
