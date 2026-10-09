<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fec4cjbkq.css';
import '../../css/n/n4sn-05th.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="fec4cjbkq"/><path class="n4sn-05th"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:chevron-left-square-20-bold" /></template>
