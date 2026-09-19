<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a59m-rccy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="a59m-rccy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-brands:codepen" /></template>
