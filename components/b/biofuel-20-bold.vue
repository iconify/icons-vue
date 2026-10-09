<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qo4j70bbm.css';
import '../../css/v/v21ewjqfm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="qo4j70bbm"/><path class="v21ewjqfm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:biofuel-20-bold" /></template>
