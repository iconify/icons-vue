<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j1kdqfrps.css';
import '../../css/c/cg7d2pfom.css';
import '../../css/r/r_d7t_bew.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j1kdqfrps"/><circle class="cg7d2pfom"/><circle class="r_d7t_bew"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bx-comment-dots" /></template>
