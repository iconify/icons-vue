<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/elr6iiype.css';
import '../../css/c/cycdfo7sy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="elr6iiype"/><path class="cycdfo7sy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:ai-hand" /></template>
