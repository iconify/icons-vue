<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fcc25bptl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fcc25bptl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:brightness" /></template>
