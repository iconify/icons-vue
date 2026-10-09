<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hqo5_yb0w.css';
import '../../css/k/kut36cotc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="hqo5_yb0w"/><path class="kut36cotc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:hvdc-converter-20-bold" /></template>
