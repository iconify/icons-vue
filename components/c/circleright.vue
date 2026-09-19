<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dr-s6ybza.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="dr-s6ybza"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:circleright" /></template>
