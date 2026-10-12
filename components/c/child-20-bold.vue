<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nbndoibgc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="nbndoibgc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:child-20-bold" /></template>
