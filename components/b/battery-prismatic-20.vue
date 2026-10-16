<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k6c9yjbgf.css';
import '../../css/p/po1u_tchm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="k6c9yjbgf"/><path class="po1u_tchm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:battery-prismatic-20" /></template>
