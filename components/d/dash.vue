<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vxhzq60ui.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="vxhzq60ui"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:dash" /></template>
