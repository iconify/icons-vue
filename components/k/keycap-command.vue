<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e74r5rbfq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="e74r5rbfq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:keycap-command" /></template>
