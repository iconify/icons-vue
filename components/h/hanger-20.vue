<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/juj97tbkw.css';
import '../../css/l/lsr8k0bex.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="juj97tbkw"/><path class="lsr8k0bex"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:hanger-20" /></template>
