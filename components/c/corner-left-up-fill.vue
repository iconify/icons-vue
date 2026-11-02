<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/grf4x6b4m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="grf4x6b4m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:corner-left-up-fill" /></template>
