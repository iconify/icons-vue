<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pr2ao-b5d.css';
import '../../css/q/quh-_jkrk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="pr2ao-b5d"/><path class="quh-_jkrk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:bell-off-20-bold" /></template>
