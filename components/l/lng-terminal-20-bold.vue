<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c10rf7bkz.css';
import '../../css/e/em_yc89qg.css';
import '../../css/i/iyvdefbei.css';
import '../../css/b/by_69xb5j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="c10rf7bkz"/><path class="em_yc89qg"/><path class="iyvdefbei"/><path class="by_69xb5j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:lng-terminal-20-bold" /></template>
