<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zr0py_b6k.css';
import '../../css/x/xuyp_ezqr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="zr0py_b6k"/><path class="xuyp_ezqr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:face-mask-48-bold" /></template>
