<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s5jpcwbws.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="s5jpcwbws"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="osmic:exit-14" /></template>
