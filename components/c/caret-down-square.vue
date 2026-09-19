<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h2u5p3b1m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h2u5p3b1m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:caret-down-square" /></template>
