<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fl3ojlbrj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="fl3ojlbrj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:lettered-list-20-solid" /></template>
