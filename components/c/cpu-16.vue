<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gdm_9fbmg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="gdm_9fbmg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:cpu-16" /></template>
