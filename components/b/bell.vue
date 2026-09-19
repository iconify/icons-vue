<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yf9rteblo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="yf9rteblo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:bell" /></template>
