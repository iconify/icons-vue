<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y63y_obeb.css';
import '../../css/i/ixud4xmsj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="y63y_obeb"/><path clip-rule="evenodd" class="ixud4xmsj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:compass-solid" /></template>
