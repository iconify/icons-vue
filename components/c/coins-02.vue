<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wth82uiax.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wth82uiax"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:coins-02" /></template>
