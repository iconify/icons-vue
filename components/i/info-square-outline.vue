<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hexx2yb1s.css';
import '../../css/e/epahso09d.css';
import '../../css/g/g4e643m4g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hexx2yb1s"/><path class="epahso09d"/><path clip-rule="evenodd" class="g4e643m4g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:info-square-outline" /></template>
