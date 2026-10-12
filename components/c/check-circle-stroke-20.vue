<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m8oetz7xx.css';
import '../../css/f/fdag88jzj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="m8oetz7xx"/><path class="fdag88jzj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:check-circle-stroke-20" /></template>
