<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/th0kx1-kp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="th0kx1-kp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uiw:file-jpg" /></template>
