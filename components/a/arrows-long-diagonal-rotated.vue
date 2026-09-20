<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a0m25c.css';
import '../../css/r/reng8d.css';
import '../../css/y/ycmuno.css';
import '../../css/s/so-from-16.css';
import '../../css/s/so-to-0.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a0m25c reng8d"/><path class="a0m25c ycmuno"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="line-md:arrows-long-diagonal-rotated" /></template>
