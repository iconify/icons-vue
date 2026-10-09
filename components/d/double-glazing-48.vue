<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zk-8-cbtr.css';
import '../../css/e/eczeehbxy.css';
import '../../css/d/df1n7oboy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="zk-8-cbtr"/><path class="eczeehbxy"/><path class="df1n7oboy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:double-glazing-48" /></template>
