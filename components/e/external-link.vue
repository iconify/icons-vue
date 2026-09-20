<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gzwy0zbjv.css';
import '../../css/j/j7gs3mbhr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gzwy0zbjv"/><path class="j7gs3mbhr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="prime:external-link" /></template>
