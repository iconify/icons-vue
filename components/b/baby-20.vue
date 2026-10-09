<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o_vbgsb4a.css';
import '../../css/e/e4z-0xbtc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="o_vbgsb4a"/><path class="e4z-0xbtc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:baby-20" /></template>
