<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sp5ysukwo.css';
import '../../css/r/rve223_3q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sp5ysukwo"/><path class="rve223_3q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:commit-24" /></template>
