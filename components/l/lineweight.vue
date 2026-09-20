<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zzea66lvs.css';
import '../../css/u/ujyghec7j.css';
import '../../css/e/ewlmhxmrx.css';
import '../../css/b/brjj83bkz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":21,"height":21};
const content = `<g class="zzea66lvs"><rect class="ujyghec7j"/><path class="ewlmhxmrx"/><path class="brjj83bkz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="system-uicons:lineweight" /></template>
