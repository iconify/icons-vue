<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mgfo819ll.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="mgfo819ll"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:envelope-in-slot" /></template>
