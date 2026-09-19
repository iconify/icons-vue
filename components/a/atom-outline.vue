<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qg37c11oy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qg37c11oy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:atom-outline" /></template>
