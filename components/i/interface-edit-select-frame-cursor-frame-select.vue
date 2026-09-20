<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hnz5lbemc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="hnz5lbemc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:interface-edit-select-frame-cursor-frame-select" /></template>
