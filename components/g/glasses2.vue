<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zki3xmbyr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zki3xmbyr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:glasses2" /></template>
