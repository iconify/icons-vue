<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p5r0r42lp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="p5r0r42lp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:forward-bar-16-solid" /></template>
