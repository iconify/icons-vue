<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u4vb3mbqk.css';
import '../../css/o/ol95ujbyo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u4vb3mbqk"/><path class="ol95ujbyo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:inj" /></template>
