<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l7cvs3lqd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l7cvs3lqd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:hand-pointer-right" /></template>
