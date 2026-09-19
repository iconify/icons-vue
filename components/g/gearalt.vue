<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/ppzs3erlm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="ppzs3erlm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:gearalt" /></template>
