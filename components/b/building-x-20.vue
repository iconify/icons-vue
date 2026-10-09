<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h1kol59_x.css';
import '../../css/s/sk3pmyb5m.css';
import '../../css/h/h9o4a4caa.css';
import '../../css/k/kqbd9jytf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="h1kol59_x"/><path class="sk3pmyb5m"/><path class="h9o4a4caa"/><path class="kqbd9jytf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:building-x-20" /></template>
