<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wm5j5xizl.css';
import '../../css/k/kbq43k7wn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="wm5j5xizl"/><path class="kbq43k7wn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:discount-20-bold" /></template>
