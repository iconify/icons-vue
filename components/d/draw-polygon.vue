<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yhwy3sbru.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="yhwy3sbru"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:draw-polygon" /></template>
