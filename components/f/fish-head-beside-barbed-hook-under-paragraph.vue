<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kfoz3-mbt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="kfoz3-mbt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:fish-head-beside-barbed-hook-under-paragraph" /></template>
