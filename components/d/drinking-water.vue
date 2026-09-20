<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sk08j9bet.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="sk08j9bet"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:drinking-water" /></template>
