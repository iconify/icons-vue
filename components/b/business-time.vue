<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zplly2b-w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="zplly2b-w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:business-time" /></template>
