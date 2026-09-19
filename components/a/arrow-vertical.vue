<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ri_arhbfk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ri_arhbfk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:arrow-vertical" /></template>
