<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j1id930iv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j1id930iv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:distribute-vertical-top" /></template>
