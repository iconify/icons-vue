<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/asornzyio.css';
import '../../css/e/elstku5yi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="asornzyio"/><path class="elstku5yi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:alarm-clock-off-20-bold" /></template>
