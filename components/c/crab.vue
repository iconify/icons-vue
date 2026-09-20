<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q7_65fbjg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="q7_65fbjg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:crab" /></template>
