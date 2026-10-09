<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zxik2jbrv.css';
import '../../css/b/b4orwhbsl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="zxik2jbrv"/><path class="b4orwhbsl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:draught-proofing-48" /></template>
