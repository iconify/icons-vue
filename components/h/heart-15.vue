<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dwqiw3okt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="dwqiw3okt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:heart-15" /></template>
