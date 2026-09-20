<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q9s6yip2j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="q9s6yip2j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:f22-raptor-fighter-jet" /></template>
