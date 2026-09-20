<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ee1eie8lx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="ee1eie8lx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:dribble-solid" /></template>
