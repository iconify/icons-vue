<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vik6htbnq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="vik6htbnq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="entypo:ccw" /></template>
