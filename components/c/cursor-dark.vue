<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pazmnhbnx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":466.73,"height":532.09};
const content = `<path class="pazmnhbnx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:cursor-dark" /></template>
