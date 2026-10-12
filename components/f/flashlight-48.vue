<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fu10s8xbg.css';
import '../../css/l/lnj0vzkpp.css';
import '../../css/e/e8x7bixqn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="fu10s8xbg"/><path class="lnj0vzkpp"/><path class="e8x7bixqn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:flashlight-48" /></template>
