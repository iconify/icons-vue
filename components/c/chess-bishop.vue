<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wjnvrp3pf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wjnvrp3pf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:chess-bishop" /></template>
