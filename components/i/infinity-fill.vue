<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t0jw-c0us.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t0jw-c0us"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:infinity-fill" /></template>
