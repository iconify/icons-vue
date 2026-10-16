<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zb2bgubhg.css';
import '../../css/i/iat97dbph.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="zb2bgubhg"/><path class="iat97dbph"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:battery-pouch-20" /></template>
