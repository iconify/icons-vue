<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ntt-te-ig.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ntt-te-ig"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-truck" /></template>
