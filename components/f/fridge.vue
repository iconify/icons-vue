<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yn_7obc0p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yn_7obc0p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:fridge" /></template>
