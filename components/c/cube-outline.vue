<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/no18gackv.css';
import '../../css/e/e9f-1ebjm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="no18gackv"/><path class="e9f-1ebjm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:cube-outline" /></template>
