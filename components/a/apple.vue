<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ry7vstmdh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ry7vstmdh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uim:apple" /></template>
