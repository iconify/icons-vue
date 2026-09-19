<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vghglv62h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":472};
const content = `<path class="vghglv62h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:assignment-o" /></template>
