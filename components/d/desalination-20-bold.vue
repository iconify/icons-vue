<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w7m1t5brv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="w7m1t5brv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:desalination-20-bold" /></template>
