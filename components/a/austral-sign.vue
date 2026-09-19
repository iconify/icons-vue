<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p_wi9y41m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="p_wi9y41m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:austral-sign" /></template>
