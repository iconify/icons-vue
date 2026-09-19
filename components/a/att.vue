<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qt6gr-b0x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qt6gr-b0x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:att" /></template>
