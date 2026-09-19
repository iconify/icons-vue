<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/odyie6but.css';
import '../../css/e/en-3d656m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="odyie6but"/><path class="en-3d656m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-arrow-dropright" /></template>
