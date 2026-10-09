<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yoe3avbru.css';
import '../../css/o/okm62lwzp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="yoe3avbru"/><path class="okm62lwzp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:eye-20-bold" /></template>
