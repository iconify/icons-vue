<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qm8uiwbzj.css';
import '../../css/w/wcp6j0b8w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="qm8uiwbzj"/><path class="wcp6j0b8w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:connector-chademo-20-bold" /></template>
