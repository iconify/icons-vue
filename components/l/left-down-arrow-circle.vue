<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c33a4rbqa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c33a4rbqa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:left-down-arrow-circle" /></template>
