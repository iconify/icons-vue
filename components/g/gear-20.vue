<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d381xzbzn.css';
import '../../css/s/sethd29la.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="d381xzbzn"/><path class="sethd29la"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:gear-20" /></template>
