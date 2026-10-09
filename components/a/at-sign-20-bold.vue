<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/okm62lwzp.css';
import '../../css/j/jlel-zbdq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="okm62lwzp"/><path class="jlel-zbdq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:at-sign-20-bold" /></template>
