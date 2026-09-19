<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/collrmb7w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="collrmb7w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:arrow-down-left-square" /></template>
