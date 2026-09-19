<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/y/y200nyy4c.css';
import '../../css/t/tn5vw1rfn.css';
import '../../css/c/cmpm5kb0f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="y200nyy4c"/><path class="tn5vw1rfn"/><path clip-rule="evenodd" class="cmpm5kb0f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:blood-a-p" /></template>
