<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m6qtzmbeo.css';
import '../../css/y/ybtqz23gr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="m6qtzmbeo"/><path class="ybtqz23gr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:entrance-15" /></template>
