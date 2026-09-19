<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rwq5dfatl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rwq5dfatl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bx-shopping-bag" /></template>
