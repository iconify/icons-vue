<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/az4cwab1h.css';
import '../../css/o/ouobwmwuo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="az4cwab1h"/><path class="ouobwmwuo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:battery-empty-20" /></template>
