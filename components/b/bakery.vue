<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sbqn-4-rf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="sbqn-4-rf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:bakery" /></template>
