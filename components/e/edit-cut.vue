<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dcu0ohh7w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="dcu0ohh7w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zondicons:edit-cut" /></template>
