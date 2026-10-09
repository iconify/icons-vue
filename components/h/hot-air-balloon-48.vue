<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d7x4h2b-v.css';
import '../../css/j/jzue8hbld.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="d7x4h2b-v"/><path class="jzue8hbld"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:hot-air-balloon-48" /></template>
