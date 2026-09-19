<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z-wqvvv2r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="z-wqvvv2r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:file-graphics-filled" /></template>
