<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gs8vflbzf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gs8vflbzf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:backpack-fill" /></template>
