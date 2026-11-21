<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n-kgrhb0e.css';
import '../../css/s/s4yvy-5kt.css';
import '../../css/p/ptl4ptbdc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="n-kgrhb0e"/><path class="s4yvy-5kt"/><path class="ptl4ptbdc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:bug-outline" /></template>
