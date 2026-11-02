<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f3-aeb-6p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f3-aeb-6p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:ease-out-control-point-fill" /></template>
