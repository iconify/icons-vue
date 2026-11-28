<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mv2a0ygbj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mv2a0ygbj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:carrot" /></template>
