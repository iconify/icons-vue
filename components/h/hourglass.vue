<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u72deestk.css';
import '../../css/a/a41-ntbbp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="u72deestk"/><path class="a41-ntbbp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:hourglass" /></template>
