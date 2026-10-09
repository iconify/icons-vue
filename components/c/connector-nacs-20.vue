<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/or3w-hr2p.css';
import '../../css/i/i5nzyoqoz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="or3w-hr2p"/><path class="i5nzyoqoz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:connector-nacs-20" /></template>
