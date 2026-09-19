<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uvir7eh3z.css';
import '../../css/c/c4bzylu5l.css';
import '../../css/m/m3lczlbgo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="uvir7eh3z"/><path class="c4bzylu5l"/><path class="m3lczlbgo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flat-color-icons:genealogy" /></template>
