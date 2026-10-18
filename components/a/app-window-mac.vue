<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qxfn2sbdi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qxfn2sbdi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:app-window-mac" /></template>
