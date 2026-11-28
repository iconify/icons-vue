<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lzsf0vb4b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lzsf0vb4b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:chalkboard" /></template>
