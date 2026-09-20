<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mwhb53btz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="mwhb53btz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:coffee-mug-and-pawprint" /></template>
