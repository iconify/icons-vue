<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wd39qiwhy.css';
import '../../css/m/mn-eum1fs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wd39qiwhy"/><path class="mn-eum1fs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:branching-paths-up-bold-duotone" /></template>
