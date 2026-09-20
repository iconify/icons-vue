<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ur2c4ccsm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ur2c4ccsm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="proicons:branch-fork-2" /></template>
