<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vctwy0bcs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vctwy0bcs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:hand-dollar" /></template>
