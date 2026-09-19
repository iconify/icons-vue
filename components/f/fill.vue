<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b_ej5mbjj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="b_ej5mbjj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:fill" /></template>
