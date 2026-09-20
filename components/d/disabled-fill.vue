<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z40mujsla.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z40mujsla"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:disabled-fill" /></template>
