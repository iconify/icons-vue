<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w20l3vtqj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":21,"height":21};
const content = `<path class="w20l3vtqj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="system-uicons:bell" /></template>
