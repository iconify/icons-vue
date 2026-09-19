<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/utly6nbpe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="utly6nbpe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:arrow-resize" /></template>
