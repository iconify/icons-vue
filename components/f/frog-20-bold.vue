<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jwnv2zbmo.css';
import '../../css/q/q0rdytb4g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="jwnv2zbmo"/><path class="q0rdytb4g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:frog-20-bold" /></template>
