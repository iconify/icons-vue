<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cf2i7pbgc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cf2i7pbgc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:bangladeshi-taka" /></template>
