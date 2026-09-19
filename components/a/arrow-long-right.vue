<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rti4-ty4m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="rti4-ty4m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="entypo:arrow-long-right" /></template>
