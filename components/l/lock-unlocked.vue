<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mo2qolbcc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="mo2qolbcc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:lock-unlocked" /></template>
