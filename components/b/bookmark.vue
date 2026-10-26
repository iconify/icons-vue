<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yfpe-fj8i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="yfpe-fj8i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="doodle-icons:bookmark" /></template>
