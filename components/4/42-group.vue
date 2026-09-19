<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sainanfrz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="sainanfrz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-brands:42-group" /></template>
