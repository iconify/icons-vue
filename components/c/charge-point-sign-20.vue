<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m2eh8bdrp.css';
import '../../css/e/ewna1ybwf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="m2eh8bdrp"/><path class="ewna1ybwf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:charge-point-sign-20" /></template>
