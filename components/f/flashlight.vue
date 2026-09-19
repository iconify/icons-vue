<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rlv7y6brq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="rlv7y6brq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="entypo:flashlight" /></template>
