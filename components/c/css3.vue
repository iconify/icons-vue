<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jy65xx2-p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1792,"height":1600};
const content = `<path class="jy65xx2-p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:css3" /></template>
