<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r9kyeodza.css';
import '../../css/t/t_0rrslox.css';
import '../../css/w/wxma-tm4b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r9kyeodza"/><path class="t_0rrslox"/><circle class="wxma-tm4b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="circum:instagram" /></template>
