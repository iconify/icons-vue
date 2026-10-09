<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xro2jqn5o.css';
import '../../css/q/qe8sicbkp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="xro2jqn5o"/><path class="qe8sicbkp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:cloud-sun-20-bold" /></template>
