<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j8fx0t0nh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j8fx0t0nh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:bricks" /></template>
