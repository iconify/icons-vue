<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hbbx21bsu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="hbbx21bsu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:domino" /></template>
