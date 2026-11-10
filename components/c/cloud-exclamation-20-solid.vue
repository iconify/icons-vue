<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vvh0w_r3l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="vvh0w_r3l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:cloud-exclamation-20-solid" /></template>
