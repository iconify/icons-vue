<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qdd6rybyq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":768};
const content = `<path class="qdd6rybyq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:foodtray" /></template>
