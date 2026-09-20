<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p2civt24x.css';
import '../../css/v/vbo9mcctp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="p2civt24x"/><path class="vbo9mcctp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="medical-icon:i-respiratory" /></template>
