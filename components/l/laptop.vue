<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fa0z2b_vv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fa0z2b_vv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:laptop" /></template>
