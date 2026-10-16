<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j0topkbwv.css';
import '../../css/w/w673-_bht.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="j0topkbwv"/><path class="w673-_bht"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:magma-chamber-20" /></template>
