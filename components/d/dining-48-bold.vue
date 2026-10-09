<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wmbj85spj.css';
import '../../css/o/orpaa3b5x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="wmbj85spj"/><path class="orpaa3b5x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:dining-48-bold" /></template>
