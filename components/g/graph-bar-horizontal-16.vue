<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/myzfomb4k.css';
import '../../css/r/rw2djkcdp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="myzfomb4k"/><path class="rw2djkcdp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:graph-bar-horizontal-16" /></template>
