<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s2xhyfvup.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="s2xhyfvup"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:bird-20-bold" /></template>
