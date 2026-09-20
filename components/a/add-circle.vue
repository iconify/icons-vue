<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mo4hawhan.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="mo4hawhan"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:add-circle" /></template>
