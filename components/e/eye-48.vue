<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bmxr2fy_x.css';
import '../../css/j/j3eacdoxs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="bmxr2fy_x"/><path class="j3eacdoxs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:eye-48" /></template>
