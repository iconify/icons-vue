<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c_4nh7rzj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c_4nh7rzj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:between-horizontal-end" /></template>
