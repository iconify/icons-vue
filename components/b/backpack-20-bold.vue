<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wz3cfsc3k.css';
import '../../css/p/pkhcb0o2g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="wz3cfsc3k"/><path class="pkhcb0o2g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:backpack-20-bold" /></template>
